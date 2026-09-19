<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/c/cimf4bblu.css';
import '../../css/w/wcw8hj87u.css';
import '../../css/k/kz5pr1h-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cimf4bblu"/><path class="wcw8hj87u"/><path class="kz5pr1h-q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:stack-star" {...props}></Icon>
