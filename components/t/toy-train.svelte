<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/e/ec_xsy4gs.css';
import '../../css/b/bf9hqaclw.css';
import '../../css/a/az8wk3mni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="ec_xsy4gs"/><circle class="bf9hqaclw"/><path class="az8wk3mni"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:toy-train" {...props}></Icon>
