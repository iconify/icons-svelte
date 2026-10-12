<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ki9tfbbtw.css';
import '../../css/v/vfhe1wb7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ki9tfbbtw"/><path class="vfhe1wb7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:ship-filled" {...props}></Icon>
