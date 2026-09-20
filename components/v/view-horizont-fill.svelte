<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g7v2-ye3h.css';
import '../../css/r/rfrpfefci.css';
import '../../css/e/eg4pfcc0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g7v2-ye3h"/><path class="rfrpfefci"/><path clip-rule="evenodd" class="eg4pfcc0n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:view-horizont-fill" {...props}></Icon>
