<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwtoeebil.css';
import '../../css/j/jg4fprb3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vwtoeebil"/><path class="jg4fprb3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:view-off" {...props}></Icon>
