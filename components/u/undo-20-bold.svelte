<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g22-s43ip.css';
import '../../css/f/f4_61hgfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g22-s43ip"/><path class="f4_61hgfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:undo-20-bold" {...props}></Icon>
