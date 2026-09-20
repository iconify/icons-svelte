<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3tt_w7bl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v3tt_w7bl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:tips-double-filled" {...props}></Icon>
