<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ho15aj4xr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ho15aj4xr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:unregistry-light" {...props}></Icon>
