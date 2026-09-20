<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/va3pi2mwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="va3pi2mwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:sound-down-filled" {...props}></Icon>
