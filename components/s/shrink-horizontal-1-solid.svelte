<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cevem_bkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cevem_bkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:shrink-horizontal-1-solid" {...props}></Icon>
