<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/h7xnus5-e.css';
import '../../css/u/unefcsbmw.css';
import '../../css/a/anua2ob4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="h7xnus5-e"/><path class="unefcsbmw"/><path class="anua2ob4h wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:watch" {...props}></Icon>
