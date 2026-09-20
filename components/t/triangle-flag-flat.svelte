<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i4-9ft8yr.css';
import '../../css/w/wjd-1y1hf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="i4-9ft8yr"/><path clip-rule="evenodd" class="wjd-1y1hf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:triangle-flag-flat" {...props}></Icon>
