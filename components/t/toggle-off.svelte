<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcld88i4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gcld88i4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:toggle-off" {...props}></Icon>
