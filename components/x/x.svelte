<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vs0efx8dm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vs0efx8dm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:x" {...props}></Icon>
