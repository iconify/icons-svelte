<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zaumeeb-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zaumeeb-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:table-fill-20" {...props}></Icon>
