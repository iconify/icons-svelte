<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-b55xleh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z-b55xleh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:trash" {...props}></Icon>
