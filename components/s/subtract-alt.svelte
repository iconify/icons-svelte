<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qoi3q_b_l.css';
import '../../css/q/q_qiu8wtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qoi3q_b_l"/><path class="q_qiu8wtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:subtract-alt" {...props}></Icon>
