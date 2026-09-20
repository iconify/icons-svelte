<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vslx7zj_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vslx7zj_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:sd-card-filled" {...props}></Icon>
