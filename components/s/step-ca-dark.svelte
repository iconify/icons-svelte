<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3-7u3bsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m3-7u3bsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:step-ca-dark" {...props}></Icon>
