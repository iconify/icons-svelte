<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fuhedbkjt.css';
import '../../css/x/x64jix1xj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fuhedbkjt"/><path class="x64jix1xj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:user-arrow-left-filled" {...props}></Icon>
