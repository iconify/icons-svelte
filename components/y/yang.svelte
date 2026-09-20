<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqbek7buq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqbek7buq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:yang" {...props}></Icon>
