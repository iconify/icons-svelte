<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zanfd_b2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zanfd_b2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:share" {...props}></Icon>
