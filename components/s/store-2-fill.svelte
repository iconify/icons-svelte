<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7-p5eb0s.css';
import '../../css/e/e2w581g2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s7-p5eb0s"/><path class="e2w581g2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:store-2-fill" {...props}></Icon>
