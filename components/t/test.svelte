<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yily_k3_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yily_k3_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:test" {...props}></Icon>
