<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_rsiugdn.css';
import '../../css/y/y9b85obej.css';
import '../../css/z/zy2mkqs2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d_rsiugdn"/><path class="y9b85obej"/><path clip-rule="evenodd" class="zy2mkqs2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:signpost-2-outline" {...props}></Icon>
