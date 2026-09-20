<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikcwavbgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ikcwavbgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:spotlight-beam" {...props}></Icon>
