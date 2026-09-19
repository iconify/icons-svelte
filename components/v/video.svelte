<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-c8q9x4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-c8q9x4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:video" {...props}></Icon>
