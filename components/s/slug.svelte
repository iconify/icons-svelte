<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pap4jeb5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pap4jeb5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:slug" {...props}></Icon>
