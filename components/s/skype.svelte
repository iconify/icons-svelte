<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nscdonb0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="nscdonb0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:skype" {...props}></Icon>
