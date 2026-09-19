<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha6dnnprf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ha6dnnprf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:square-deskpro" {...props}></Icon>
