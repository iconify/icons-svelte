<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/ch19v3bee.css';
import '../../css/v/vi6jplbfg.css';
import '../../css/y/yg3s2lbnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ch19v3bee"/><path clip-rule="evenodd" class="vi6jplbfg"/><path class="yg3s2lbnw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:target-duotone-line" {...props}></Icon>
