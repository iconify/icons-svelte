<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukh96f2tw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ukh96f2tw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:slash-square-fill" {...props}></Icon>
