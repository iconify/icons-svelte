<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnawqtehn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lnawqtehn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:signal-full-01" {...props}></Icon>
