<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kw_fdvb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="kw_fdvb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:treasure-chest" {...props}></Icon>
