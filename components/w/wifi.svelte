<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdbfw3b6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hdbfw3b6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:wifi" {...props}></Icon>
