<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qo0nwpb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qo0nwpb6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:thinking" {...props}></Icon>
