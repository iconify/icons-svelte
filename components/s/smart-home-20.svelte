<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dz30y8b3r.css';
import '../../css/g/gtn82neio.css';
import '../../css/e/e3lx9cbyl.css';
import '../../css/j/jgfshtvfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dz30y8b3r"/><path class="gtn82neio"/><path class="e3lx9cbyl"/><path class="jgfshtvfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smart-home-20" {...props}></Icon>
