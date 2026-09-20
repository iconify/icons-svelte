<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iytak3z-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iytak3z-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:smile-dizzy" {...props}></Icon>
