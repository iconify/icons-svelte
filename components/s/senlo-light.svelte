<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prmy9wtgl.css';
import '../../css/m/miwt5_b7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="prmy9wtgl"/><path class="miwt5_b7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:senlo-light" {...props}></Icon>
