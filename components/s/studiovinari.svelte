<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn2-7pgaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="jn2-7pgaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:studiovinari" {...props}></Icon>
