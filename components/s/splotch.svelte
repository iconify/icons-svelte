<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzroh3b8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="tzroh3b8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:splotch" {...props}></Icon>
