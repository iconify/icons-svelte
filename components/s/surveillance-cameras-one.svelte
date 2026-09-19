<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/g/g7lpxxbmh.css';
import '../../css/l/lo1qem4dc.css';
import '../../css/h/h8tqvyb5j.css';
import '../../css/b/b64n8bc3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="g7lpxxbmh"/><path class="lo1qem4dc"/><path class="h8tqvyb5j"/><path class="b64n8bc3q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:surveillance-cameras-one" {...props}></Icon>
