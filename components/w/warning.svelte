<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sguy3dbrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sguy3dbrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:warning" {...props}></Icon>
