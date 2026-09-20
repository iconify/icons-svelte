<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/uo3e6gbze.css';
import '../../css/i/i0b8n-y7j.css';
import '../../css/h/hl78y5ebu.css';
import '../../css/s/srjd9cjvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="uo3e6gbze"/><path class="i0b8n-y7j"/><path class="hl78y5ebu"/><path class="srjd9cjvi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:users-group-rounded-bold" {...props}></Icon>
