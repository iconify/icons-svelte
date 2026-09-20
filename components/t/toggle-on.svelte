<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ur9frkzhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ur9frkzhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:toggle-on" {...props}></Icon>
