<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnce0pb6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vnce0pb6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:street-view" {...props}></Icon>
