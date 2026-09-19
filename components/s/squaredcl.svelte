<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyr2jybbi.css';
import '../../css/c/cu-wwpbhr.css';
import '../../css/u/una0uy64j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cyr2jybbi"/><path class="cu-wwpbhr"/><path class="una0uy64j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:squaredcl" {...props}></Icon>
