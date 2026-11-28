<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9m24lbpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary v9m24lbpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:type-duotone" {...props}></Icon>
