<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fx2g9l0aa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fx2g9l0aa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:signal-hspa-plus" {...props}></Icon>
