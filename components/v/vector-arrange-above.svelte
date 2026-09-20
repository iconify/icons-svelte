<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_8arlbee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_8arlbee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:vector-arrange-above" {...props}></Icon>
