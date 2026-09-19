<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkv_76b3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pkv_76b3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:women" {...props}></Icon>
