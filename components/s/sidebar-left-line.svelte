<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzt5isb9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vzt5isb9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sidebar-left-line" {...props}></Icon>
