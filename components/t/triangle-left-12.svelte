<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h86kn5bdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="h86kn5bdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:triangle-left-12" {...props}></Icon>
