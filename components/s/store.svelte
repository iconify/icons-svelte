<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl0xw-snl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="bl0xw-snl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:store" {...props}></Icon>
