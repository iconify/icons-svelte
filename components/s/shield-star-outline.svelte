<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/on5jz7bsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="on5jz7bsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:shield-star-outline" {...props}></Icon>
