<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tihaa0pcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="tihaa0pcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:square-stack-3d-up-slash-fill" {...props}></Icon>
