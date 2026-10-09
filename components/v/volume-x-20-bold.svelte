<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvsucgsri.css';
import '../../css/b/bfzo5mbpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bvsucgsri"/><path class="bfzo5mbpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:volume-x-20-bold" {...props}></Icon>
