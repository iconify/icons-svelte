<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmeo3-b1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmeo3-b1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:skip-forward-fill" {...props}></Icon>
