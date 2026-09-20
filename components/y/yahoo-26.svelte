<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhc8dieas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="bhc8dieas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:yahoo-26" {...props}></Icon>
