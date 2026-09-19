<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7b52bcxl.css';
import '../../css/z/zvlz7ab9o.css';
import '../../css/r/roko4zy8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c7b52bcxl"/><path class="zvlz7ab9o"/><path class="roko4zy8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:server-sharp" {...props}></Icon>
