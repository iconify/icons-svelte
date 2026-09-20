<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrio91b3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lrio91b3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:sticky-note-2-line" {...props}></Icon>
