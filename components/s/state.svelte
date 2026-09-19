<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocjh6qbnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ocjh6qbnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:state" {...props}></Icon>
