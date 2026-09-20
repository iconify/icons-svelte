<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qh7_ghbdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qh7_ghbdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:scale-outline" {...props}></Icon>
