<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/s/svpwambew.css';
import '../../css/l/lwo-nbbud.css';
import '../../css/v/v2l5ufa5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="svpwambew"/><circle class="lwo-nbbud"/><path class="v2l5ufa5d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:unordered-list" {...props}></Icon>
