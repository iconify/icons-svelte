<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hf1ev1bin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hf1ev1bin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:shield-16" {...props}></Icon>
