<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf2tuqcuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pf2tuqcuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:spacing-small-16" {...props}></Icon>
