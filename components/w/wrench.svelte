<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lf33gv8ni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lf33gv8ni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:wrench" {...props}></Icon>
