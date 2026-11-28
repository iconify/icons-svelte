<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enyryrbow.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/l-em5n3wu.css';
import '../../css/t/td39edehy.css';
import '../../css/g/gxcdsu0rs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="enyryrbow secondary"/><g class="dt0cm9dhy primary"><path class="l-em5n3wu"/><path class="td39edehy"/><path class="gxcdsu0rs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:sushi-duo" {...props}></Icon>
