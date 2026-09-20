<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1f5hpb-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i1f5hpb-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:signal-variant" {...props}></Icon>
