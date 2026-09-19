<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrag1rbbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="hrag1rbbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:trello" {...props}></Icon>
