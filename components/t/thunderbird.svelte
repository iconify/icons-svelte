<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oegj9vb9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oegj9vb9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:thunderbird" {...props}></Icon>
