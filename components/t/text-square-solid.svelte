<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8ul3vxjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k8ul3vxjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:text-square-solid" {...props}></Icon>
