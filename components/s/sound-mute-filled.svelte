<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uffnlp-lf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uffnlp-lf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:sound-mute-filled" {...props}></Icon>
