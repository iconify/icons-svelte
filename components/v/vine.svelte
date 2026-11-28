<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/v1u1iuzxy.css';
import '../../css/a/a5dkqgbtz.css';
import '../../css/d/deea3zlhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="v1u1iuzxy"/><path class="a5dkqgbtz"/><path class="deea3zlhh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:vine" {...props}></Icon>
