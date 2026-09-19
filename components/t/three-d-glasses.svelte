<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/z/z3lx3r37r.css';
import '../../css/l/lgog-_bex.css';
import '../../css/o/owbah4bpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="z3lx3r37r"/><path class="lgog-_bex"/><path clip-rule="evenodd" class="owbah4bpd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:three-d-glasses" {...props}></Icon>
