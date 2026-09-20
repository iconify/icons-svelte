<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtp5fgbmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dtp5fgbmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:sticky-note-2-fill-2" {...props}></Icon>
