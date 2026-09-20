<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2vb22kcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u2vb22kcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:user-check-solid" {...props}></Icon>
