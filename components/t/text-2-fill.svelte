<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qds8d4bih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qds8d4bih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:text-2-fill" {...props}></Icon>
