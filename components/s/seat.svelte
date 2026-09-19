<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdhhczbfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gdhhczbfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:seat" {...props}></Icon>
