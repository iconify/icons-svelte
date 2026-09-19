<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1ax_lbqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":960};
const content = `<path class="j1ax_lbqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:stamp" {...props}></Icon>
