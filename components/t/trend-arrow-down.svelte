<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhyksccpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uhyksccpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:trend-arrow-down" {...props}></Icon>
