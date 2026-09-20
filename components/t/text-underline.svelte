<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxjcc1i8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="zxjcc1i8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:text-underline" {...props}></Icon>
