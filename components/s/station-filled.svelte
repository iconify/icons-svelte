<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mspp6ty_p.css';
import '../../css/e/eawnq8bpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mspp6ty_p"/><path class="eawnq8bpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:station-filled" {...props}></Icon>
