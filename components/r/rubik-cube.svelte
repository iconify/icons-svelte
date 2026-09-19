<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfwvdk0fj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qfwvdk0fj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:rubik-cube" {...props}></Icon>
