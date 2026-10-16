<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytc7x632j.css';
import '../../css/d/dygm4jbzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ytc7x632j"/><path class="dygm4jbzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:silicon-20" {...props}></Icon>
