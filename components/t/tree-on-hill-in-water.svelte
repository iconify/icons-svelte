<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz4so0yad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gz4so0yad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tree-on-hill-in-water" {...props}></Icon>
