<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsvcz2bdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qsvcz2bdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:sitemap-filled" {...props}></Icon>
