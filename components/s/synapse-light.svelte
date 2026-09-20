<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcgqwnbco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lcgqwnbco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:synapse-light" {...props}></Icon>
