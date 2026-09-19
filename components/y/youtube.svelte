<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idwcf8bvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="idwcf8bvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:youtube" {...props}></Icon>
