<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tklug5bkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":14};
const content = `<path class="tklug5bkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:union" {...props}></Icon>
