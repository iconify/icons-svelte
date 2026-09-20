<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-il2px1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-il2px1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:svgdotjs" {...props}></Icon>
