<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln_8z-bww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ln_8z-bww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:start-event-multiple" {...props}></Icon>
