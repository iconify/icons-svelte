<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4x1z3brk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4x1z3brk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:threads" {...props}></Icon>
