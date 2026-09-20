<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_3us-pxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-5};
const content = `<path class="w_3us-pxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:switch-left" {...props}></Icon>
