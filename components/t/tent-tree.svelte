<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddjkb6b-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ddjkb6b-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:tent-tree" {...props}></Icon>
