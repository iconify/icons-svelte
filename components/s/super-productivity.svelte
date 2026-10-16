<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dinz6tf1u.css';
import '../../css/y/y5-o4cbgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="dinz6tf1u"/><path class="y5-o4cbgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:super-productivity" {...props}></Icon>
