<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wx5vx6b6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wx5vx6b6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:wall-fuzo-h" {...props}></Icon>
