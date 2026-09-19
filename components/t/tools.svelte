<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf5vfgp4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="pf5vfgp4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:tools" {...props}></Icon>
