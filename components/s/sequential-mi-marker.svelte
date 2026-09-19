<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg1q73zov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2000,"height":2000};
const content = `<path class="zg1q73zov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:sequential-mi-marker" {...props}></Icon>
