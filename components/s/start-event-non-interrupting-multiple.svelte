<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytmp8tbaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ytmp8tbaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:start-event-non-interrupting-multiple" {...props}></Icon>
