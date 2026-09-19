<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2w28gbbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a2w28gbbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:text-recognition" {...props}></Icon>
