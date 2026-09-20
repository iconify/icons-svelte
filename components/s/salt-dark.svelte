<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eonil2bft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eonil2bft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:salt-dark" {...props}></Icon>
