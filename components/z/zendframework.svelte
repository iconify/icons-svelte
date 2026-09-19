<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec7m1jb_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":896};
const content = `<path class="ec7m1jb_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:zendframework" {...props}></Icon>
