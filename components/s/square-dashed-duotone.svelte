<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m35ze94yj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m35ze94yj primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-dashed-duotone" {...props}></Icon>
