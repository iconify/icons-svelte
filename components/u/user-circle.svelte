<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/i/icp-mdbnu.css';
import '../../css/r/roc0omyox.css';
import '../../css/z/zhqqtqbzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="icp-mdbnu"/><path class="roc0omyox"/><path class="zhqqtqbzi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:user-circle" {...props}></Icon>
