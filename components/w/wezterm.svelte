<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkdi-641j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gkdi-641j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:wezterm" {...props}></Icon>
