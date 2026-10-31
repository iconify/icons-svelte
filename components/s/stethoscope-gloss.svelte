<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ood22d57s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ood22d57s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:stethoscope-gloss" {...props}></Icon>
