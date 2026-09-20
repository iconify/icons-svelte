<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyduw2bud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dyduw2bud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:server-plus" {...props}></Icon>
