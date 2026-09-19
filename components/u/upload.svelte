<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z59djne8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z59djne8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:upload" {...props}></Icon>
