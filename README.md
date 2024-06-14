import random

def luminous_lake_exploration():
    print("Welcome to the Luminous Lake...")
    print("You arrive at a mystical lake, where the waters glow with a soft, enchanting light.")

    while True:
        print("\nYou gaze upon the luminous lake...")
        input("Press Enter to continue exploring...")

        event = random.randint(1, 5)

        if event == 1:
            print("You see shimmering fish darting beneath the glowing surface.")
        elif event == 2:
            print("A gentle breeze creates ripples, scattering light in beautiful patterns.")
        elif event == 3:
            print("You discover a hidden cove, its walls illuminated with bioluminescent moss.")
        elif event == 4:
            print("A flock of luminous birds flies overhead, their feathers glowing in the twilight.")
        elif event == 5:
            print("The water's glow intensifies, revealing an ancient, submerged statue.")

        choice = input("\nContinue exploring the luminous lake? (yes/no): ").lower()
        if choice != 'yes':
            break

    print("\nYour exploration of the luminous lake concludes.")
    print("Thank you for experiencing the enchantment of the Luminous Lake.")

# Start exploring the luminous lake
luminous_lake_exploration()
