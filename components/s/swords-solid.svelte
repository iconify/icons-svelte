<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_24t7api.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f_24t7api"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:swords-solid" {...props}></Icon>
