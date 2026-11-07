<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ut9wycb0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ut9wycb0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:star-fall-minimalistic-2-outline" {...props}></Icon>
