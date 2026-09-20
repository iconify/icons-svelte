<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xh82h5geo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xh82h5geo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:subtitles-fill" {...props}></Icon>
