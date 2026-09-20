<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y87ybjbjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y87ybjbjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:table-density-expanded" {...props}></Icon>
