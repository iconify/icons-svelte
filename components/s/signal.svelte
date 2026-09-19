<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bun7qr1sn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bun7qr1sn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:signal" {...props}></Icon>
