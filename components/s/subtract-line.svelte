<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyq_zyido.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lyq_zyido"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:subtract-line" {...props}></Icon>
