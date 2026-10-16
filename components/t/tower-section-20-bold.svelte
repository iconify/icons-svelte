<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m53sf3b9t.css';
import '../../css/y/ylritbb4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m53sf3b9t"/><path class="ylritbb4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tower-section-20-bold" {...props}></Icon>
