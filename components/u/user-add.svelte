<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwyxhbcim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwyxhbcim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:user-add" {...props}></Icon>
