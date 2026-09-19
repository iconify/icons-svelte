<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5mn0ab7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="e5mn0ab7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:wpexplorer" {...props}></Icon>
