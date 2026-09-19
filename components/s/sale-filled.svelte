<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hng-1kbdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hng-1kbdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:sale-filled" {...props}></Icon>
