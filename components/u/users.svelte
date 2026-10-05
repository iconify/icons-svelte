<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/e/e0twvnfzl.css';
import '../../css/l/lstqv8blb.css';
import '../../css/y/yfgq3cchb.css';
import '../../css/x/x5wgfjb0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="e0twvnfzl"/><path class="lstqv8blb"/><path class="yfgq3cchb"/><path class="x5wgfjb0q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:users" {...props}></Icon>
