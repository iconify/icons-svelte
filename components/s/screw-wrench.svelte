<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtfewx74d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2000,"height":2000};
const content = `<path class="xtfewx74d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:screw-wrench" {...props}></Icon>
