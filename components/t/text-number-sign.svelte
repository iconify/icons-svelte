<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1bus9b3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v1bus9b3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:text-number-sign" {...props}></Icon>
