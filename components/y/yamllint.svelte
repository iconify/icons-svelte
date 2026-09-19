<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alm0-u9-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="alm0-u9-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:yamllint" {...props}></Icon>
