<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7642b9dp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="m7642b9dp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:signal" {...props}></Icon>
