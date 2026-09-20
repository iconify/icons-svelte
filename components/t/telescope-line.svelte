<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcf_bgnsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bcf_bgnsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:telescope-line" {...props}></Icon>
