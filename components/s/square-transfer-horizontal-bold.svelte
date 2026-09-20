<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzopzdowi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qzopzdowi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-transfer-horizontal-bold" {...props}></Icon>
