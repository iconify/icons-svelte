<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkdb5_b2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mkdb5_b2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:ryanair" {...props}></Icon>
