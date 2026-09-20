<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/h/hoqg9vbdg.css';
import '../../css/k/ke7d84ibd.css';
import '../../css/w/wq2wc4bco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hoqg9vbdg"/><path class="ke7d84ibd"/><path class="wq2wc4bco"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:timer-pause" {...props}></Icon>
