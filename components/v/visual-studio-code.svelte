<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw9csqb-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bw9csqb-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:visual-studio-code" {...props}></Icon>
