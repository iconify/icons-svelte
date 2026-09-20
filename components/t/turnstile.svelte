<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhplffbdf.css';
import '../../css/z/zv-6rgbbp.css';
import '../../css/p/pfmh85w5h.css';
import '../../css/s/sxrpgcc4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zhplffbdf"/><path class="zv-6rgbbp"/><path class="pfmh85w5h"/><path class="sxrpgcc4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:turnstile" {...props}></Icon>
