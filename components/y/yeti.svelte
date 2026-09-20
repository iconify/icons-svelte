<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrtg7zr2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vrtg7zr2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:yeti" {...props}></Icon>
