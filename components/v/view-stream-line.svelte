<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2saatb0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w2saatb0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:view-stream-line" {...props}></Icon>
