<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtt3ujtqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xtt3ujtqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:sticky-note-off" {...props}></Icon>
