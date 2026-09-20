<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1ymmx26k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g1ymmx26k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:safari-light" {...props}></Icon>
