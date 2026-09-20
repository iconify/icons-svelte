<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hya1gml3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hya1gml3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:search-16" {...props}></Icon>
