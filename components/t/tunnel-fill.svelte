<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r69w_s5qv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r69w_s5qv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tunnel-fill" {...props}></Icon>
