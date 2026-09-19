<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqqgrl6yn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oqqgrl6yn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:skype" {...props}></Icon>
