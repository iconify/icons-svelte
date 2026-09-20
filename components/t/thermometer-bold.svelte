<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ziks3bbat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ziks3bbat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:thermometer-bold" {...props}></Icon>
