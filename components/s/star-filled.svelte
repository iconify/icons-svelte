<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwmmpzbaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pwmmpzbaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:star-filled" {...props}></Icon>
