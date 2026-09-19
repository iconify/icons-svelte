<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilyn7bcgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ilyn7bcgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:upload" {...props}></Icon>
