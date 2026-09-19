<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fveij088p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fveij088p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:square-wave" {...props}></Icon>
