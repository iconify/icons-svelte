<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/riy8ysb2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="riy8ysb2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:snow" {...props}></Icon>
