<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjk99yo8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qjk99yo8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:soundcloud" {...props}></Icon>
