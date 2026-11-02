<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijrakd5dp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ijrakd5dp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tyre-line" {...props}></Icon>
