<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srmks4o_f.css';
import '../../css/h/h6on4ibgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="srmks4o_f"/><path class="h6on4ibgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:train-1" {...props}></Icon>
