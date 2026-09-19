<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvlge_bte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vvlge_bte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:scooter-alt-filled" {...props}></Icon>
