<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv74m9bnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pv74m9bnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:time-one-outline" {...props}></Icon>
