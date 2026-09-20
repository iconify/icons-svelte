<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7740dnjq.css';
import '../../css/j/jclmsksby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u7740dnjq"/><path class="jclmsksby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:shuffle-line" {...props}></Icon>
