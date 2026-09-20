<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/urz-4cihd.css';
import '../../css/j/j3iqtac1n.css';
import '../../css/v/vo_vnys1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="urz-4cihd"/><path clip-rule="evenodd" class="j3iqtac1n"/><path class="vo_vnys1f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:user-scan-duotone" {...props}></Icon>
