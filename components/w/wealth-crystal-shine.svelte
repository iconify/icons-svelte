<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3qcpwb4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g3qcpwb4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:wealth-crystal-shine" {...props}></Icon>
