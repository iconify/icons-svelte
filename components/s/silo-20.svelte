<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ik-dwhbem.css';
import '../../css/b/bp5qez_qk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ik-dwhbem"/><path class="bp5qez_qk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:silo-20" {...props}></Icon>
