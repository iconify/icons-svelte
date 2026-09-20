<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eydgy3bvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="eydgy3bvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:signage-3" {...props}></Icon>
