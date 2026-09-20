<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvitn_tfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gvitn_tfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:udotsdotnews" {...props}></Icon>
