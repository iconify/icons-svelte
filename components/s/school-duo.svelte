<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/x/x09dvzbrc.css';
import '../../css/s/s5-9cqlug.css';
import '../../css/b/bymrjbwvt.css';
import '../../css/b/b3n8gubwl.css';
import '../../css/b/ba_pjzfdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="x09dvzbrc"/><path class="s5-9cqlug wm-a"/><path class="bymrjbwvt wm-a"/><path class="b3n8gubwl"/><path class="ba_pjzfdu wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:school-duo" {...props}></Icon>
