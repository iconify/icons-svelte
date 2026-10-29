<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec_0r_tga.css';
import '../../css/n/nx9eqfb9e.css';
import '../../css/a/aloyasbca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ec_0r_tga wm-k"/><path class="nx9eqfb9e wm-a"/><path class="aloyasbca wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:upload" {...props}></Icon>
