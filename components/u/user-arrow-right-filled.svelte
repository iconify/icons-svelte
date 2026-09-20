<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg_3mbzwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cg_3mbzwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:user-arrow-right-filled" {...props}></Icon>
