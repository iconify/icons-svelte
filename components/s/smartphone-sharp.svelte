<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlxio1l9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qlxio1l9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:smartphone-sharp" {...props}></Icon>
