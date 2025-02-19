<script>
	// import ScoreBadge from './overlay/ScoreBadge.svelte';
	// import InfoBanner from './overlay/InfoBanner.svelte';
	// import TotalScoreCard from './overlay/TotalScoreCard.svelte';
	// import TimerCard from './overlay/TimerCard.svelte';
	// import TeamBanner from './overlay/TeamBanner.svelte';
	import Results from './results/Results.svelte';

</script>
<div>HI</div>
<results>
    <Results></Results>
</results>
<style>
    /*results {
        .container {
            position: absolute;
            display: flex;
            flex-direction: column;
            align-items: flex-end;
            top: 1.2vw;
            right: 1.2vw;
            gap: 0.8vw;

            #results {
                position: static;
            }

            .away {
                opacity: 0;

                &#await {
                    transform: translateY(calc(-100% - 1.2vw));

                    & + #results {
                        position: absolute;
                        top: 0;
                    }
                }

                &#results {
                    transform: translateX(calc(100% + 1.2vw));
                }
            }
        }
    }*/
</style>