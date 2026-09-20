<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/j/j7lgzkbaq.css';
import '../../css/x/xnxh71obt.css';
import '../../css/h/hvgzjjb7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j7lgzkbaq"/><path class="xnxh71obt"/><path class="hvgzjjb7d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:sms-search" {...props}></Icon>
