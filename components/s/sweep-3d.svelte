<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocawmz1rc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ocawmz1rc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:sweep-3d" {...props}></Icon>
