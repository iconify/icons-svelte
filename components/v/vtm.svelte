<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbkaf_btf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wbkaf_btf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:vtm" {...props}></Icon>
