<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdrf1fb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rdrf1fb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:thumbsdown-solid" {...props}></Icon>
