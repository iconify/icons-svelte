<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cml5n7irm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cml5n7irm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:twake-drive-dark" {...props}></Icon>
