<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by_na8eqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="by_na8eqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:stackoverflow" {...props}></Icon>
