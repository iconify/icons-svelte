<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/y/yb7rs8bok.css';
import '../../css/k/kfn71cctn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yb7rs8bok"/><path class="kfn71cctn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-dot-dashed-line-duotone" {...props}></Icon>
