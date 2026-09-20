<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lofrdjd_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":360,"height":362};
const content = `<path clip-rule="evenodd" class="lofrdjd_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:whatsapp" {...props}></Icon>
