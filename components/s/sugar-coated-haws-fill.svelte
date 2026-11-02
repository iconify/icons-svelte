<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlwo-kb1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xlwo-kb1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sugar-coated-haws-fill" {...props}></Icon>
