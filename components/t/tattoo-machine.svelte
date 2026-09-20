<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvdel6b_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gvdel6b_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:tattoo-machine" {...props}></Icon>
