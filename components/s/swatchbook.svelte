<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wo0fe9mij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wo0fe9mij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:swatchbook" {...props}></Icon>
