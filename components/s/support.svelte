<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlt2-rbhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tlt2-rbhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:support" {...props}></Icon>
