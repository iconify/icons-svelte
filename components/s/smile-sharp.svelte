<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqe88najq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nqe88najq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:smile-sharp" {...props}></Icon>
