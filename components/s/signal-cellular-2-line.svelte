<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnixv7h1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pnixv7h1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:signal-cellular-2-line" {...props}></Icon>
