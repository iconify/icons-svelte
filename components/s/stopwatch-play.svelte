<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nphau5bcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nphau5bcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:stopwatch-play" {...props}></Icon>
