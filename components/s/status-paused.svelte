<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6nnf9-3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path clip-rule="evenodd" class="a6nnf9-3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:status-paused" {...props}></Icon>
