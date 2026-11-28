<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/te6x4btrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="te6x4btrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:shuffle-solid" {...props}></Icon>
