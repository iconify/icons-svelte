<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsh5-wo2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":524,"height":797};
const content = `<path class="bsh5-wo2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:underscore" {...props}></Icon>
