<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jk_ymsbeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="jk_ymsbeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:tree" {...props}></Icon>
