<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/s827tjbfm.css';
import '../../css/i/isb6qg8bj.css';
import '../../css/a/acycy-bpy.css';
import '../../css/s/s7oqvk7xy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="s827tjbfm"/><path class="isb6qg8bj"/><path clip-rule="evenodd" class="acycy-bpy"/><path class="s7oqvk7xy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:washing-machine-duotone" {...props}></Icon>
