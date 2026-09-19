<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/matslfbya.css';
import '../../css/b/b1ecs5fbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="matslfbya"/><path class="b1ecs5fbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:terminal" {...props}></Icon>
