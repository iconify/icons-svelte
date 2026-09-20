<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2fiuw9jr.css';
import '../../css/k/koneki24a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m2fiuw9jr"/><path clip-rule="evenodd" class="koneki24a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tag-2-fill" {...props}></Icon>
