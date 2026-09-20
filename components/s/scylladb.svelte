<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/baa3s6bhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="baa3s6bhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:scylladb" {...props}></Icon>
