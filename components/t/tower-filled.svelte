<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th_wgybyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="th_wgybyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:tower-filled" {...props}></Icon>
