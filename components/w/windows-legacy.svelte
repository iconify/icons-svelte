<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7qt6_goq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n7qt6_goq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:windows-legacy" {...props}></Icon>
