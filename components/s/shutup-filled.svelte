<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8r-3erqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c8r-3erqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:shutup-filled" {...props}></Icon>
