<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a46888bgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="a46888bgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:screenshot" {...props}></Icon>
