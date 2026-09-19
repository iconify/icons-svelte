<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxlew9bzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxlew9bzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:traffic" {...props}></Icon>
