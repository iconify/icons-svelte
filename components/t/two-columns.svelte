<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrbn-ftbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrbn-ftbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:two-columns" {...props}></Icon>
