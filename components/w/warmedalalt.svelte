<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2mfbmb1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="v2mfbmb1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:warmedalalt" {...props}></Icon>
