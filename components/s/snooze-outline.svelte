<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/buijfg4ca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="buijfg4ca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:snooze-outline" {...props}></Icon>
