<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uc95oj5yc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uc95oj5yc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:sov" {...props}></Icon>
