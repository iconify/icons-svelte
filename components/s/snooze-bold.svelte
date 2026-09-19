<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze4n_9xuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ze4n_9xuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:snooze-bold" {...props}></Icon>
