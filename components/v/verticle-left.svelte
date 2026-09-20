<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkjdmcv7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lkjdmcv7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:verticle-left" {...props}></Icon>
