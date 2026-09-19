<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhvh4xbwq.css';
import '../../css/f/fj4btac-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhvh4xbwq"/><path class="fj4btac-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:zoom-in" {...props}></Icon>
