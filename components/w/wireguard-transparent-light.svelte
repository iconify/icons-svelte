<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nn1s74bhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nn1s74bhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wireguard-transparent-light" {...props}></Icon>
