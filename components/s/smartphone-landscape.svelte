<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/la181rmii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":384};
const content = `<path class="la181rmii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:smartphone-landscape" {...props}></Icon>
