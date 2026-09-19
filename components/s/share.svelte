<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxrskd1xp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oxrskd1xp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:share" {...props}></Icon>
