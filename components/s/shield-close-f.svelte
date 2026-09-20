<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlv_0xbwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-1.5};
const content = `<path class="zlv_0xbwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:shield-close-f" {...props}></Icon>
