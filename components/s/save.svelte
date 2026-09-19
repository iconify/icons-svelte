<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jho-fuw1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jho-fuw1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:save" {...props}></Icon>
