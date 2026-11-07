<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqc3njjlu.css';
import '../../css/s/skij5-7yd.css';
import '../../css/d/d03fu6wuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iqc3njjlu"/><path clip-rule="evenodd" class="skij5-7yd"/><path class="d03fu6wuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:turntable-music-note-bold-duotone" {...props}></Icon>
