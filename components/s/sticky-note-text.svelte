<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxvwipb7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxvwipb7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sticky-note-text" {...props}></Icon>
