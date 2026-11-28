<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd2ixsb_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cd2ixsb_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:spell-check-solid" {...props}></Icon>
