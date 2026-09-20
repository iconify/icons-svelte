<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r87d8bbxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r87d8bbxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:tencent" {...props}></Icon>
