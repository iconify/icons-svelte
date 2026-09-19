<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3469cbxe.css';
import '../../css/n/n8ytkn-vp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u3469cbxe"/><path class="n8ytkn-vp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:view" {...props}></Icon>
