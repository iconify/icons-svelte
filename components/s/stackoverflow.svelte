<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xf84qumns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xf84qumns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:stackoverflow" {...props}></Icon>
