<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/ga3b3ijty.css';
import '../../css/v/vn993tbah.css';
import '../../css/r/r7fsfvpov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="ft5dv1b6b"><rect class="ga3b3ijty"/><path clip-rule="evenodd" class="vn993tbah"/><path clip-rule="evenodd" class="r7fsfvpov"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="skill-icons:unrealengine" {...props}></Icon>
