<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxc2ifb9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":31,"height":24};
const content = `<path class="wxc2ifb9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:soundcloud" {...props}></Icon>
