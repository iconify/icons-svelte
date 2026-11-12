<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lg2k2gbvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lg2k2gbvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:users-down" {...props}></Icon>
