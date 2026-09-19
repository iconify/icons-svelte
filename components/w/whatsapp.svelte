<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti7oxnffl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ti7oxnffl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:whatsapp" {...props}></Icon>
