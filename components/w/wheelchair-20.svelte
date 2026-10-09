<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u48dvzb0i.css';
import '../../css/j/j9cnkbbzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u48dvzb0i"/><path class="j9cnkbbzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wheelchair-20" {...props}></Icon>
