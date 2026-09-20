<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajifrufrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ajifrufrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:sim-card-2-filled" {...props}></Icon>
