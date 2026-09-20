<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrn1n11ow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mrn1n11ow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:whatsapp-dark" {...props}></Icon>
