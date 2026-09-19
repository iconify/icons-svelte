<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s750qgbyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s750qgbyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:vimeo" {...props}></Icon>
