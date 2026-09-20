<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac9ldtb9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ac9ldtb9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:volume" {...props}></Icon>
