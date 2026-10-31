<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1x_6zbkv.css';
import '../../css/g/gk5dn-bts.css';
import '../../css/n/ndsoh9bgy.css';
import '../../css/t/tomk5q72m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="d1x_6zbkv"/><path class="gk5dn-bts"/><path class="ndsoh9bgy"/><path class="tomk5q72m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:syria" {...props}></Icon>
