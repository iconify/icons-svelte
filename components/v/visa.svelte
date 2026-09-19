<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5be5-ssr.css';
import '../../css/j/jn7q2h3yu.css';
import '../../css/o/o4xfpac0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e5be5-ssr"/><path class="jn7q2h3yu"/><path class="o4xfpac0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:visa" {...props}></Icon>
