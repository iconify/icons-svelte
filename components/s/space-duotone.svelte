<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmqcxacwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary tmqcxacwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:space-duotone" {...props}></Icon>
