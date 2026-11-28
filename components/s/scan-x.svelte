<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jv5hbjbfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jv5hbjbfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:scan-x" {...props}></Icon>
