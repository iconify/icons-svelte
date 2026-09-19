<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7nc_vb4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="s7nc_vb4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:tooth" {...props}></Icon>
