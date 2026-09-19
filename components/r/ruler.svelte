<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bulg0db2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="bulg0db2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:ruler" {...props}></Icon>
