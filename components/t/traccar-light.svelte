<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3zme3brp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e3zme3brp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:traccar-light" {...props}></Icon>
