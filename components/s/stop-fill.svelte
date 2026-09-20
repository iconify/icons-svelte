<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsodg2gky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jsodg2gky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:stop-fill" {...props}></Icon>
