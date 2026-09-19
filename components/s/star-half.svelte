<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_jz5xwqo.css';
import '../../css/n/nx8_58b1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x_jz5xwqo"/><path class="nx8_58b1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:star-half" {...props}></Icon>
