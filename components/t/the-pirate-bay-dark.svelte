<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tiemq2b-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tiemq2b-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:the-pirate-bay-dark" {...props}></Icon>
