<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3y2h-bte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r3y2h-bte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:speakingheadinsilhouette" {...props}></Icon>
