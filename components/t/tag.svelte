<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k6pc56b3v.css';
import '../../css/d/dsacgh5ov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="k6pc56b3v"/><circle transform="rotate(-45 7.738 7.738)" class="dsacgh5ov"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:tag" {...props}></Icon>
