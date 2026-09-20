<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llq52qemd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="llq52qemd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:signal" {...props}></Icon>
