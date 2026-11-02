<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogkky7bkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ogkky7bkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:square-arrow-down-fill" {...props}></Icon>
