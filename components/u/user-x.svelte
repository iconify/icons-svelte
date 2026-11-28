<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvzxq1brn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lvzxq1brn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:user-x" {...props}></Icon>
