<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bobuj8b3z.css';
import '../../css/n/nh6el8bqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bobuj8b3z"/><ellipse class="nh6el8bqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:toilet-paper-line" {...props}></Icon>
