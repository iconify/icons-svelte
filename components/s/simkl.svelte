<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5b-05ttx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t5b-05ttx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:simkl" {...props}></Icon>
