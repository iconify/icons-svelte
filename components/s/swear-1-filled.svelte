<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqfloy9hp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uqfloy9hp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:swear-1-filled" {...props}></Icon>
