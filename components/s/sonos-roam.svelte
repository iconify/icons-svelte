<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1ok9-bvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j1ok9-bvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:sonos-roam" {...props}></Icon>
