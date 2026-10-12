<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqkp5ilzt.css';
import '../../css/z/zy3ocbcvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tqkp5ilzt"/><path class="zy3ocbcvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:sparkle-alt-stroke-20" {...props}></Icon>
