<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxo396bxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hxo396bxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:users-solid" {...props}></Icon>
