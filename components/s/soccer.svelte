<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5cg8fb9r.css';
import '../../css/o/oq8pnh08o.css';
import '../../css/b/bzck47bbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y5cg8fb9r"><path class="oq8pnh08o"/><path class="bzck47bbc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:soccer" {...props}></Icon>
