<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3bhubjjm.css';
import '../../css/k/ktli5dbnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v3bhubjjm"/><path class="ktli5dbnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:strapi-dark" {...props}></Icon>
