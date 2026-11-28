<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0iyypbjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o0iyypbjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:underline" {...props}></Icon>
