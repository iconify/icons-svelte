<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f4r51ccgo.css';
import '../../css/k/kz0c2chyn.css';
import '../../css/h/h3mlx2byk.css';
import '../../css/e/e6i73-02r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="f4r51ccgo"/><path class="kz0c2chyn"/><path class="h3mlx2byk"/><path class="e6i73-02r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:split-branch" {...props}></Icon>
