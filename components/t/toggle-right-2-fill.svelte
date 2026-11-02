<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygz__nb3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ygz__nb3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:toggle-right-2-fill" {...props}></Icon>
