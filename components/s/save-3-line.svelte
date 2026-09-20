<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmvjiybux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pmvjiybux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:save-3-line" {...props}></Icon>
