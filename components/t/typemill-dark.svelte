<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dj3b2hoai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dj3b2hoai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:typemill-dark" {...props}></Icon>
