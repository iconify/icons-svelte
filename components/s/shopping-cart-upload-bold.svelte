<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqnf4kbgb.css';
import '../../css/g/gxm3dk91i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fqnf4kbgb"/><path class="gxm3dk91i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:shopping-cart-upload-bold" {...props}></Icon>
