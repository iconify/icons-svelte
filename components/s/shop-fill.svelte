<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dx9pka8qs.css';
import '../../css/d/d1k3_cc9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dx9pka8qs"/><path clip-rule="evenodd" class="d1k3_cc9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:shop-fill" {...props}></Icon>
