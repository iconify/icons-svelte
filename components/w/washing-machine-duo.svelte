<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/g74ufgb1e.css';
import '../../css/d/dbwmo8bvj.css';
import '../../css/r/rwx8arbdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="g74ufgb1e"/><path class="dbwmo8bvj wm-a"/><path class="rwx8arbdh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:washing-machine-duo" {...props}></Icon>
