<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/t-5wpjwof.css';
import '../../css/o/o8mkkgbix.css';
import '../../css/c/c4_v7i59t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="t-5wpjwof"/><path class="o8mkkgbix wm-a"/><path class="c4_v7i59t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:sticky-note-duo" {...props}></Icon>
