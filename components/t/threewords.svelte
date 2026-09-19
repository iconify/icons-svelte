<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_ckt2lhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":312,"height":488};
const content = `<path class="h_ckt2lhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:threewords" {...props}></Icon>
