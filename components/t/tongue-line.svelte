<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ronm36v_x.css';
import '../../css/e/erf0i1n1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ronm36v_x"/><path class="erf0i1n1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tongue-line" {...props}></Icon>
