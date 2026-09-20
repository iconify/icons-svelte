<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/si-73mbtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="si-73mbtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:tired-solid" {...props}></Icon>
