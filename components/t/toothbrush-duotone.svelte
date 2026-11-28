<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6c_n6ydo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary q6c_n6ydo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:toothbrush-duotone" {...props}></Icon>
