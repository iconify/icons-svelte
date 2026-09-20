<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gb53x88iz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gb53x88iz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:textformat-wrap" {...props}></Icon>
