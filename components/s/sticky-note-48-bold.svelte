<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvvgk1bmy.css';
import '../../css/i/i0j09mbzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wvvgk1bmy"/><path class="i0j09mbzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sticky-note-48-bold" {...props}></Icon>
