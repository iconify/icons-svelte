<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcxx2abtz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jcxx2abtz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:superscript" {...props}></Icon>
