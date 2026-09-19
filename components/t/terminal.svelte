<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0k1xbo6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":680,"height":614};
const content = `<path class="z0k1xbo6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:terminal" {...props}></Icon>
