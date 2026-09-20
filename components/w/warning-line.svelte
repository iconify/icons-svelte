<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kflq1srsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kflq1srsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:warning-line" {...props}></Icon>
