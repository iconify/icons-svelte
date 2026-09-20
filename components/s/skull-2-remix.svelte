<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot8g6wbns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ot8g6wbns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:skull-2-remix" {...props}></Icon>
