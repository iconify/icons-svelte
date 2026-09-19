<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tge1ipiqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tge1ipiqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:spotify" {...props}></Icon>
