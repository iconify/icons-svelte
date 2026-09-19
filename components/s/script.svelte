<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjp8ftb9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fjp8ftb9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:script" {...props}></Icon>
