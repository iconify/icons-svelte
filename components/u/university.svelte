<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw9y56b6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1920,"height":1792};
const content = `<path class="zw9y56b6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:university" {...props}></Icon>
