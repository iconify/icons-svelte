<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyer2sg9u.css';
import '../../css/w/w9octyb7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tyer2sg9u"/><path class="w9octyb7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sticky-note-20-bold" {...props}></Icon>
