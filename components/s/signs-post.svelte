<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co1yhgbzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="co1yhgbzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:signs-post" {...props}></Icon>
