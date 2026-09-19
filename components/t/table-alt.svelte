<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/civ9npw1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1472};
const content = `<path class="civ9npw1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:table-alt" {...props}></Icon>
