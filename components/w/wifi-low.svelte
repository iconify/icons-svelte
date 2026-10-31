<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/p/p7j418b9p.css';
import '../../css/p/plpl1_b2t.css';
import '../../css/d/d-ca87bew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="p7j418b9p wm-shadow"/><path class="plpl1_b2t"/><path class="d-ca87bew"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-retro:wifi-low" {...props}></Icon>
