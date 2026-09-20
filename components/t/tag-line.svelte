<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wg3c--bsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wg3c--bsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:tag-line" {...props}></Icon>
