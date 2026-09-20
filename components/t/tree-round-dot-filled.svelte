<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2n4pmoob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f2n4pmoob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:tree-round-dot-filled" {...props}></Icon>
