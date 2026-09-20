<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyt0lf95d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wyt0lf95d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:volleyball-filled" {...props}></Icon>
