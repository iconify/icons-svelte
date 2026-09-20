<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x35ffibve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x35ffibve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:yoga-half-moon-pose-1" {...props}></Icon>
