<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3xqbrbhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":304,"height":384};
const content = `<path class="c3xqbrbhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:upload" {...props}></Icon>
