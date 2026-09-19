<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4q1pjb7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a4q1pjb7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:stethoscope" {...props}></Icon>
