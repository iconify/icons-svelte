<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8dyc1zhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="w8dyc1zhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:scale-extend" {...props}></Icon>
