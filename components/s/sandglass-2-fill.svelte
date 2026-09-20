<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfwgsqbmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jfwgsqbmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sandglass-2-fill" {...props}></Icon>
