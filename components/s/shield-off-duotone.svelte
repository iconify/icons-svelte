<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flxjj8bgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="flxjj8bgf primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:shield-off-duotone" {...props}></Icon>
