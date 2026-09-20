<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lddffrb3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lddffrb3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:typescript-light" {...props}></Icon>
