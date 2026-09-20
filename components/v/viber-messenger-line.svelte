<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zix_86b2w.css';
import '../../css/k/k_1w6h3qx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zix_86b2w"/><path clip-rule="evenodd" class="k_1w6h3qx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:viber-messenger-line" {...props}></Icon>
