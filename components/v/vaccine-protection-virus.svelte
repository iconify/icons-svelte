<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/b/b8xq7u-3q.css';
import '../../css/b/brtmzlb7c.css';
import '../../css/q/qd-mihk1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b8xq7u-3q"/><path class="brtmzlb7c"/><path class="qd-mihk1s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:vaccine-protection-virus" {...props}></Icon>
