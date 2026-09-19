<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qu_3bybmc.css';
import '../../css/k/ki8ztfb6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qu_3bybmc"/><path clip-rule="evenodd" class="ki8ztfb6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:skip-prev-outline" {...props}></Icon>
