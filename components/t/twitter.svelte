<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7ybdmbxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":352,"height":488};
const content = `<path class="p7ybdmbxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:twitter" {...props}></Icon>
