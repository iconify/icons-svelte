<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urp6r9jfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="urp6r9jfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:specters-dark" {...props}></Icon>
