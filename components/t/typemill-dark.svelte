<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gugv25bse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gugv25bse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:typemill-dark" {...props}></Icon>
