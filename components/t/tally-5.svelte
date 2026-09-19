<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_jn8tb_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_jn8tb_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:tally-5" {...props}></Icon>
