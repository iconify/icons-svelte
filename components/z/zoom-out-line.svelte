<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx-_zh9uq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lx-_zh9uq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:zoom-out-line" {...props}></Icon>
