<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/sfboi1amy.css';
import '../../css/m/mlzja6boa.css';
import '../../css/l/ly23pmblx.css';
import '../../css/l/ld4zezz7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="sfboi1amy"/><path class="mlzja6boa wm-a"/><path class="ly23pmblx"/><path class="ld4zezz7d wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:train-duo" {...props}></Icon>
