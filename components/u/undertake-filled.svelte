<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6qbz_njz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s6qbz_njz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:undertake-filled" {...props}></Icon>
