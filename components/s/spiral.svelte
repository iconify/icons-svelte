<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_0ev4bkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="r_0ev4bkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:spiral" {...props}></Icon>
