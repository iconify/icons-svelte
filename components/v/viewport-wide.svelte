<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqqo41bsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bqqo41bsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:viewport-wide" {...props}></Icon>
