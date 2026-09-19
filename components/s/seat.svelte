<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yi5enj7yp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="yi5enj7yp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:seat" {...props}></Icon>
