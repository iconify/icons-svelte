<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gus-xabuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gus-xabuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:share" {...props}></Icon>
