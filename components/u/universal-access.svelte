<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shba36i9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="shba36i9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:universal-access" {...props}></Icon>
