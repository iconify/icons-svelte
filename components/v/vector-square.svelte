<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfj-4o4tk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mfj-4o4tk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:vector-square" {...props}></Icon>
