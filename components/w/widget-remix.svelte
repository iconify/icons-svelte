<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qc1765b3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qc1765b3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:widget-remix" {...props}></Icon>
