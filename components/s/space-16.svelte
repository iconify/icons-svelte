<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8dgv7ect.css';
import '../../css/c/c4hlqdbyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n8dgv7ect"/><path class="c4hlqdbyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:space-16" {...props}></Icon>
