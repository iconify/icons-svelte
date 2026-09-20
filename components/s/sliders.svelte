<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtowsomii.css';
import '../../css/z/zg9mj5bvu.css';
import '../../css/l/lxc48fbno.css';
import '../../css/b/brca0-h_r.css';
import '../../css/x/xs8w2qkuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><path class="zg9mj5bvu"/><circle class="lxc48fbno"/><path class="brca0-h_r"/><circle class="xs8w2qkuj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:sliders" {...props}></Icon>
