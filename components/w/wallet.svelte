<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpho4wbxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zpho4wbxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:wallet" {...props}></Icon>
