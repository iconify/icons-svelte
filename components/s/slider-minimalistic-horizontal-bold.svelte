<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvskk7nlf.css';
import '../../css/d/d9yqzeb3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lvskk7nlf"/><path clip-rule="evenodd" class="d9yqzeb3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:slider-minimalistic-horizontal-bold" {...props}></Icon>
