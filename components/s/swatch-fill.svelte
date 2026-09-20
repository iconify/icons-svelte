<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zl2xf4b2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zl2xf4b2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:swatch-fill" {...props}></Icon>
