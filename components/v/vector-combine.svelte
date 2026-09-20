<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvwt5tb-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jvwt5tb-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:vector-combine" {...props}></Icon>
