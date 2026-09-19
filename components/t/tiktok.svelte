<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpg56_zsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qpg56_zsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:tiktok" {...props}></Icon>
