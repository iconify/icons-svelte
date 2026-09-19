<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nta_beb7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nta_beb7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:thumbs-up" {...props}></Icon>
