<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8vpcrk_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a8vpcrk_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:script-sharp" {...props}></Icon>
