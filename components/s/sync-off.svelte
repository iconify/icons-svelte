<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsx3ph7fw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lsx3ph7fw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sync-off" {...props}></Icon>
