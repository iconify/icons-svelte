<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8_c70p_x.css';
import '../../css/f/ftery2lwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g8_c70p_x wm-k"/><path class="ftery2lwy wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:skip-back" {...props}></Icon>
