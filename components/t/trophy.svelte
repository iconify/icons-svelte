<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tui_wvwks.css';
import '../../css/i/i7bd01w6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tui_wvwks"/><path class="i7bd01w6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:trophy" {...props}></Icon>
