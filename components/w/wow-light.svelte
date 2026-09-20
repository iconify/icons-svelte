<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/m7pevhgad.css';
import '../../css/l/lquzsqb6o.css';
import '../../css/b/b9esesbic.css';
import '../../css/w/w6-q7vl-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="m7pevhgad"/><circle class="lquzsqb6o"/><circle class="b9esesbic"/><path class="w6-q7vl-y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:wow-light" {...props}></Icon>
