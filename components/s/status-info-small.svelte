<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uedkzf-5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<rect class="uedkzf-5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:status-info-small" {...props}></Icon>
