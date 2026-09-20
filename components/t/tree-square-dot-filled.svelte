<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mouct7y2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mouct7y2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:tree-square-dot-filled" {...props}></Icon>
