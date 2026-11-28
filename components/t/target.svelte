<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/r/riz3hy1-t.css';
import '../../css/y/y9ufshblj.css';
import '../../css/z/zrlh-6b7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><circle class="riz3hy1-t"/><circle class="y9ufshblj"/><path class="zrlh-6b7n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:target" {...props}></Icon>
