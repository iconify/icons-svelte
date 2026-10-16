<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3o57d_5v.css';
import '../../css/g/g_pbthpru.css';
import '../../css/v/vlpxa7bvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h3o57d_5v"/><path class="g_pbthpru"/><path class="vlpxa7bvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sun-angle-20" {...props}></Icon>
