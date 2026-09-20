<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1fub1sqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f1fub1sqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:shell-solid" {...props}></Icon>
