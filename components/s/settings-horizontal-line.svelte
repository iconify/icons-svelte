<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cq4j-lb9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cq4j-lb9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:settings-horizontal-line" {...props}></Icon>
