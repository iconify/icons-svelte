<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uay0o2xxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uay0o2xxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:saudia" {...props}></Icon>
