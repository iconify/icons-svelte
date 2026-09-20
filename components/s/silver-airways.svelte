<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss9llcb2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ss9llcb2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:silver-airways" {...props}></Icon>
