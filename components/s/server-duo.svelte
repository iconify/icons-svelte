<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/bunq_pbyx.css';
import '../../css/k/ksdsltdkn.css';
import '../../css/g/g8ehjj7yy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="bunq_pbyx"/><path class="ksdsltdkn wm-a"/><path class="g8ehjj7yy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:server-duo" {...props}></Icon>
