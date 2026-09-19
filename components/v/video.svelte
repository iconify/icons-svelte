<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w62me5ijn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w62me5ijn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:video" {...props}></Icon>
