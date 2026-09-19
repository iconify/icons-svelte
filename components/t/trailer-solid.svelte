<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx_8uzbpx.css';
import '../../css/f/fgdlr4sbs.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 hx_8uzbpx"/><path class="clr-i-solid clr-i-solid-path-2 fgdlr4sbs"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:trailer-solid" {...props}></Icon>
