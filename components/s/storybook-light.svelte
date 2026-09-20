<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0uvq1byx.css';
import '../../css/p/plbtdtgjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r0uvq1byx"/><path class="plbtdtgjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:storybook-light" {...props}></Icon>
