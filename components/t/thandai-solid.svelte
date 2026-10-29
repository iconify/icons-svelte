<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyxnp4cfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oyxnp4cfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:thandai-solid" {...props}></Icon>
