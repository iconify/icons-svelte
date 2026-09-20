<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8up-1bkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="j8up-1bkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:rounded-triangle-up-outline" {...props}></Icon>
