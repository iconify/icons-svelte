<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pibf0kb_r.css';
import '../../css/x/xts2abbvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pibf0kb_r"/><path class="xts2abbvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:scan-detail" {...props}></Icon>
