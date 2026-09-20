<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lllp7cbua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lllp7cbua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:voilib-light" {...props}></Icon>
