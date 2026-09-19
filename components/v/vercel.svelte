<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4i2dwbfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n4i2dwbfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:vercel" {...props}></Icon>
