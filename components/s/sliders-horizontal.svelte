<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xljezlftl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xljezlftl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:sliders-horizontal" {...props}></Icon>
