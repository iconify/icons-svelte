<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwt8ncc8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":488};
const content = `<path class="lwt8ncc8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:xing" {...props}></Icon>
