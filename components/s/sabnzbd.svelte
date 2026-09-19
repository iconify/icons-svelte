<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6xuw1b-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f6xuw1b-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:sabnzbd" {...props}></Icon>
