<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5bo-kbda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="h5bo-kbda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:start-event-non-interrupting-message" {...props}></Icon>
