<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/k9o9xjf6i.css';
import '../../css/g/gjs9f88_s.css';
import '../../css/t/tey93ihjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="k9o9xjf6i"/><path class="gjs9f88_s"/><path class="tey93ihjn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:unlink" {...props}></Icon>
