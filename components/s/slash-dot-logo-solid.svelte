<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxyvz461p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pxyvz461p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:slash-dot-logo-solid" {...props}></Icon>
