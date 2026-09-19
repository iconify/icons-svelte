<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cu7_tkyee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cu7_tkyee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:ticket" {...props}></Icon>
