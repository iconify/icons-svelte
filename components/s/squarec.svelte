<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_lklgblv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="e_lklgblv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:squarec" {...props}></Icon>
