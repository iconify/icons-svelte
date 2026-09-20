<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j70-_o67p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="j70-_o67p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:toll" {...props}></Icon>
