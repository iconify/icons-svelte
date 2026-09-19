<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6b1et9wp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="b6b1et9wp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:share-square" {...props}></Icon>
