<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5yr6acra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p5yr6acra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:text-align-center" {...props}></Icon>
