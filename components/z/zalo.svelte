<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/po_jy88nd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="po_jy88nd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:zalo" {...props}></Icon>
