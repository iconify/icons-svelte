<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q736f8bvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q736f8bvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:users-lock" {...props}></Icon>
