<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5djr2b9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v5djr2b9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:windows-fill-16" {...props}></Icon>
