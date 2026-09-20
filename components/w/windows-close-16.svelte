<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5rsijhuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g5rsijhuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:windows-close-16" {...props}></Icon>
