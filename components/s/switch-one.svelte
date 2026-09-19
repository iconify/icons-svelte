<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/g/gp0k69hqw.css';
import '../../css/l/lxw3yac5g.css';
import '../../css/a/a-4yy16xc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><circle class="gp0k69hqw"/><rect transform="rotate(90 36.006 19.334)" class="lxw3yac5g"/><rect transform="rotate(-180 36.006 29.852)" class="a-4yy16xc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:switch-one" {...props}></Icon>
