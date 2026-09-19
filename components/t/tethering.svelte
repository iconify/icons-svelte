<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djtt_e1bf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="djtt_e1bf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:tethering" {...props}></Icon>
