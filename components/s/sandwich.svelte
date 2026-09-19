<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yz5p2db5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yz5p2db5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:sandwich" {...props}></Icon>
