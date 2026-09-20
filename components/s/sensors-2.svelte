<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0bs2lpng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x0bs2lpng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:sensors-2" {...props}></Icon>
