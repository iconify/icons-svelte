<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnr1s3bub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="rnr1s3bub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:text-paragraph" {...props}></Icon>
