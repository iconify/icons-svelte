<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvhe_nbhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="gvhe_nbhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:tablets" {...props}></Icon>
