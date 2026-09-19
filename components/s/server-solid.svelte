<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tq-hjpgxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tq-hjpgxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:server-solid" {...props}></Icon>
