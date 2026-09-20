<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/woj_30btd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="woj_30btd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:typeform" {...props}></Icon>
