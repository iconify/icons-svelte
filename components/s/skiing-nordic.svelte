<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkz0r345s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="kkz0r345s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:skiing-nordic" {...props}></Icon>
