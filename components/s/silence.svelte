<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg6v_r6gv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cg6v_r6gv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:silence" {...props}></Icon>
