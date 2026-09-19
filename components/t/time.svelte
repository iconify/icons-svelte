<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d47xi2b9o.css';
import '../../css/b/b1ahei25d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d47xi2b9o"/><path class="b1ahei25d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:time" {...props}></Icon>
