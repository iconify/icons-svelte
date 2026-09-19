<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hq_s-dbfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hq_s-dbfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:warning" {...props}></Icon>
