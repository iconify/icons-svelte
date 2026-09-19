<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3fptrb1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="t3fptrb1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:user-graduate" {...props}></Icon>
