<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smq69y8wv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="smq69y8wv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:shop" {...props}></Icon>
