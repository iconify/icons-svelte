<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htigj1b9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="htigj1b9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:torah" {...props}></Icon>
