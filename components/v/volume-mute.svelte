<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqnawabpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xqnawabpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:volume-mute" {...props}></Icon>
