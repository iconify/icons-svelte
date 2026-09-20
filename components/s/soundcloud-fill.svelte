<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvm7w0qkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tvm7w0qkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:soundcloud-fill" {...props}></Icon>
