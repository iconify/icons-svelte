<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i86379gaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i86379gaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:thumbtack-solid" {...props}></Icon>
