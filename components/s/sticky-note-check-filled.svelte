<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxvb6cctw.css';
import '../../css/n/n5sg21b7n.css';
import '../../css/z/zj890cb5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxvb6cctw"/><path class="n5sg21b7n"/><path class="zj890cb5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:sticky-note-check-filled" {...props}></Icon>
