<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plrwr-bwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="plrwr-bwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:sliders-16" {...props}></Icon>
