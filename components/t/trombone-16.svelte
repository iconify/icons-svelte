<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv_s9x15n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gv_s9x15n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:trombone-16" {...props}></Icon>
