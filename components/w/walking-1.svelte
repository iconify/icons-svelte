<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm4cycc0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dm4cycc0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate-color:walking-1" {...props}></Icon>
