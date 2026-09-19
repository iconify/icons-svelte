<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ua-shzb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ua-shzb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:uppointingredtriangle" {...props}></Icon>
