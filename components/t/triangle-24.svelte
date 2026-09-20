<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmc9s-k4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmc9s-k4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:triangle-24" {...props}></Icon>
