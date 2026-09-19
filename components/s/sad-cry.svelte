<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jv01ljeqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="jv01ljeqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:sad-cry" {...props}></Icon>
