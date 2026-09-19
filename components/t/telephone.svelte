<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2t_mpb7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":16};
const content = `<path class="z2t_mpb7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:telephone" {...props}></Icon>
