<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uexsjcbrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="uexsjcbrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:text-flow-rows-solid" {...props}></Icon>
