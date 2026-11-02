<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe1gcdc0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xe1gcdc0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sidebar-right-close-line" {...props}></Icon>
