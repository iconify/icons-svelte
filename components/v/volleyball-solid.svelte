<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_d_h4bhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_d_h4bhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:volleyball-solid" {...props}></Icon>
