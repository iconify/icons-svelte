<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwj0upb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zwj0upb9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sportarr-dark" {...props}></Icon>
