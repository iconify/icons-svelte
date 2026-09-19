<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm7jd5bvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rm7jd5bvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:usa-flag" {...props}></Icon>
