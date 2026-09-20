<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5kx_xpqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i5kx_xpqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:web-grid-alt" {...props}></Icon>
