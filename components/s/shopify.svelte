<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmmc7xi2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-3,"top":-2};
const content = `<path class="gmmc7xi2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:shopify" {...props}></Icon>
