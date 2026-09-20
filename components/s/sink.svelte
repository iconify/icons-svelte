<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/up6v01b5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="up6v01b5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:sink" {...props}></Icon>
