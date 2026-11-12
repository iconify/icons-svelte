<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqx5e5n2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rqx5e5n2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:united-airlines-dark" {...props}></Icon>
