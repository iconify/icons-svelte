<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo997g_ca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zo997g_ca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ruler-alt" {...props}></Icon>
