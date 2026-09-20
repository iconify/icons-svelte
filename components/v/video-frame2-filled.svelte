<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0gifg4or.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0gifg4or"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:video-frame2-filled" {...props}></Icon>
