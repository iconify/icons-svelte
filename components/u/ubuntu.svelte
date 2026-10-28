<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8wq5kgjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x8wq5kgjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ubuntu" {...props}></Icon>
