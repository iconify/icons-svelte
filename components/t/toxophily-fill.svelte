<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h302ntxcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h302ntxcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:toxophily-fill" {...props}></Icon>
