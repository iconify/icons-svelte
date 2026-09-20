<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh4odwcwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vh4odwcwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:subtitle-edit" {...props}></Icon>
