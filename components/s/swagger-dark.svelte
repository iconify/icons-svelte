<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv2bqz5ub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yv2bqz5ub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:swagger-dark" {...props}></Icon>
