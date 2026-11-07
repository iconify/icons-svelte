<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwdyy_0gr.css';
import '../../css/j/jdu2jtbuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lwdyy_0gr"/><path class="jdu2jtbuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sort-horizontal-bold-duotone" {...props}></Icon>
