<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j59tpjvbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="j59tpjvbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:search-small-solid" {...props}></Icon>
