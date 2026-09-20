<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oks2q6bhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oks2q6bhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:table-16" {...props}></Icon>
