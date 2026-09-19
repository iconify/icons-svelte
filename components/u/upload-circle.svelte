<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w11gdab4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="w11gdab4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:upload-circle" {...props}></Icon>
