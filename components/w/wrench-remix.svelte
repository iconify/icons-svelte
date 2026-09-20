<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4joqebof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="a4joqebof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:wrench-remix" {...props}></Icon>
