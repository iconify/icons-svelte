<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_eyktb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u_eyktb3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:urgency-outline" {...props}></Icon>
