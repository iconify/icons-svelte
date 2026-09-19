<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfku9-bda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="xfku9-bda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:school-circle-xmark" {...props}></Icon>
