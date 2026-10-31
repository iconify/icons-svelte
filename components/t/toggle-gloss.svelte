<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bn6qthh5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bn6qthh5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:toggle-gloss" {...props}></Icon>
