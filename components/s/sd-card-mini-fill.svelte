<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9ipceodn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m9ipceodn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:sd-card-mini-fill" {...props}></Icon>
