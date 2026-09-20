<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayt0x815c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ayt0x815c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:travis-ci" {...props}></Icon>
