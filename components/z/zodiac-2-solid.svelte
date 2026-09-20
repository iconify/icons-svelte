<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zytj7im2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zytj7im2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:zodiac-2-solid" {...props}></Icon>
