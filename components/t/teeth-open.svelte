<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfa1i2-ds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="lfa1i2-ds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:teeth-open" {...props}></Icon>
