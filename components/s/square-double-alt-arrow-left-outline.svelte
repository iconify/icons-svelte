<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqhi_gn_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vqhi_gn_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-double-alt-arrow-left-outline" {...props}></Icon>
