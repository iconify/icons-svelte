<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfkkiybgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vfkkiybgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:text-all-caps" {...props}></Icon>
