<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh38m3ble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lh38m3ble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:shield-light" {...props}></Icon>
