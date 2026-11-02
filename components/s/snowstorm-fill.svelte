<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8dax6a8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q8dax6a8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:snowstorm-fill" {...props}></Icon>
