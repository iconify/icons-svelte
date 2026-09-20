<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpprw1quh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mpprw1quh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:synology-light" {...props}></Icon>
