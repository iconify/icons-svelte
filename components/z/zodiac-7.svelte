<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zukfnb_jc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="zukfnb_jc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:zodiac-7" {...props}></Icon>
