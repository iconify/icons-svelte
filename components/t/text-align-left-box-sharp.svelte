<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov1wd7b2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ov1wd7b2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:text-align-left-box-sharp" {...props}></Icon>
