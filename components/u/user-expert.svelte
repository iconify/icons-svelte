<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chuc7emeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="chuc7emeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:user-expert" {...props}></Icon>
