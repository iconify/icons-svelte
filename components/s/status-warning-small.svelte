<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8m22gsge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="o8m22gsge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:status-warning-small" {...props}></Icon>
