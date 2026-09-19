<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/ooe2_4l1n.css';
import '../../css/i/i0gz7cuwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="ooe2_4l1n"/><path class="i0gz7cuwa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flagpack:th" {...props}></Icon>
