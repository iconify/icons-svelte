<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y42_8l0eq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y42_8l0eq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:trakt" {...props}></Icon>
