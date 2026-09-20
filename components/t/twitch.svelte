<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adnm6ebzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="adnm6ebzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:twitch" {...props}></Icon>
