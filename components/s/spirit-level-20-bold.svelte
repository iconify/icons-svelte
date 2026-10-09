<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2a3x9b1l.css';
import '../../css/n/nv5lv4auf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m2a3x9b1l"/><path class="nv5lv4auf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:spirit-level-20-bold" {...props}></Icon>
