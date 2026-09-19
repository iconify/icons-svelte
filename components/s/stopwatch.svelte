<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwcoh5b4b.css';
import '../../css/r/r-ls0rn8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zwcoh5b4b"/><path class="r-ls0rn8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:stopwatch" {...props}></Icon>
