<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iahw3kbqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":24};
const content = `<path class="iahw3kbqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:volume-mute" {...props}></Icon>
