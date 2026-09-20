<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxwofm01t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vxwofm01t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-arrow-left-down-bold" {...props}></Icon>
