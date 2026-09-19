<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wh-hi-1jy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wh-hi-1jy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:social-distancing-protect-shield-2" {...props}></Icon>
