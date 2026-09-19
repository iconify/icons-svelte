<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7zrjaq9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n7zrjaq9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:triangle-left-filled" {...props}></Icon>
