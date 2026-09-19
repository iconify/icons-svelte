<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvtzd3b0t.css';
import '../../css/j/jxpdhoeop.css';
import '../../css/z/zk3b7wb-z.css';
import '../../css/p/p-c8nc-9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="zvtzd3b0t"/><path class="jxpdhoeop"/><rect class="zk3b7wb-z"/><path class="p-c8nc-9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:today-outline" {...props}></Icon>
