<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fuwq-f-1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fuwq-f-1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:script-2-remix" {...props}></Icon>
