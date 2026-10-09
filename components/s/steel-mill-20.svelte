<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl_f1i0nt.css';
import '../../css/c/cr_3gebps.css';
import '../../css/z/z7zq9ab0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bl_f1i0nt"/><path class="cr_3gebps"/><path class="z7zq9ab0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:steel-mill-20" {...props}></Icon>
