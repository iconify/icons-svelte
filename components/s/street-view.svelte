<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iu5xwibvu.css';
import '../../css/n/nswg25bfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iu5xwibvu"/><path class="nswg25bfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:street-view" {...props}></Icon>
