<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbnu5ip9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hbnu5ip9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:square-minus-filled" {...props}></Icon>
