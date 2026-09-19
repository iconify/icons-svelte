<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8flzlb8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="s8flzlb8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:start-event-non-interrupting-parallel-multiple" {...props}></Icon>
