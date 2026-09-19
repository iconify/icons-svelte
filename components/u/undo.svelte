<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7vz9wb9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q7vz9wb9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:undo" {...props}></Icon>
