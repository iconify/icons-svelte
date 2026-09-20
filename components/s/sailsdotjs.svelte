<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2k-k1brx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z2k-k1brx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:sailsdotjs" {...props}></Icon>
