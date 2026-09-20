<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nk-5euk3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nk-5euk3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:sparkles-filled" {...props}></Icon>
