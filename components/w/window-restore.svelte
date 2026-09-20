<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0i15fbfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k0i15fbfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:window-restore" {...props}></Icon>
