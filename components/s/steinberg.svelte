<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np5colb1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="np5colb1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:steinberg" {...props}></Icon>
