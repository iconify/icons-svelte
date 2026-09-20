<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bup17yboj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bup17yboj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:sign-cross-square-solid" {...props}></Icon>
