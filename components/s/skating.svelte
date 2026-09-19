<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdteftrlc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="sdteftrlc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:skating" {...props}></Icon>
