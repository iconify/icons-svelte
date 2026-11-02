<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4sa0ghds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m4sa0ghds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:settings-4-line" {...props}></Icon>
