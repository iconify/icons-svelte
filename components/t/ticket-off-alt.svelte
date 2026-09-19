<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inc-f_bge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="inc-f_bge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:ticket-off-alt" {...props}></Icon>
