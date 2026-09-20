<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qllraju_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qllraju_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:slide-show-play-remix" {...props}></Icon>
