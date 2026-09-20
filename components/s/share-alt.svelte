<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8yi8ab8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="h8yi8ab8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:share-alt" {...props}></Icon>
