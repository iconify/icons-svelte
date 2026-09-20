<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ceyh51bqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ceyh51bqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:soundcloud-light" {...props}></Icon>
