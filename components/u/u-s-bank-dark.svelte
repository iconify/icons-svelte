<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g45c17bnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g45c17bnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:u-s-bank-dark" {...props}></Icon>
