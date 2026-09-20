<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zir0f_raf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zir0f_raf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:school-15" {...props}></Icon>
