<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xc5thce2f.css';
import '../../css/x/xo1yjrb5w.css';
import '../../css/w/wk9a195np.css';
import '../../css/x/x0qkfr1ft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="xc5thce2f"/><circle class="xo1yjrb5w"/><circle class="wk9a195np"/><path class="x0qkfr1ft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:scatter-matrix" {...props}></Icon>
