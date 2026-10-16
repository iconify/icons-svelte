<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzgrz9d2f.css';
import '../../css/j/jmwc4n-6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hzgrz9d2f"/><path class="jmwc4n-6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ups-20" {...props}></Icon>
