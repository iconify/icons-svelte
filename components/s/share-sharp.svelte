<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krt54e2yz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="krt54e2yz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:share-sharp" {...props}></Icon>
