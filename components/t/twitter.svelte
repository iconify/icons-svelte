<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbf205b_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gbf205b_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:twitter" {...props}></Icon>
