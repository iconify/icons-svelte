<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_xaaun7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="f_xaaun7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:tickets" {...props}></Icon>
