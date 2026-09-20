<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsht9ko9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dsht9ko9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:window" {...props}></Icon>
