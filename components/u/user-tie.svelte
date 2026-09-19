<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw_7son6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="rw_7son6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:user-tie" {...props}></Icon>
