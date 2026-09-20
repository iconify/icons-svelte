<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/d/ddds83y6u.css';
import '../../css/v/vr8mcipvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="icon-tabler nrj6p8qat"><path class="ddds83y6u"/><path class="vr8mcipvg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:skip-back" {...props}></Icon>
