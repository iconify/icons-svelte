<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1x_6zbkv.css';
import '../../css/d/dz--kkbng.css';
import '../../css/n/ndsoh9bgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="d1x_6zbkv"/><path class="dz--kkbng"/><path class="ndsoh9bgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:yemen" {...props}></Icon>
