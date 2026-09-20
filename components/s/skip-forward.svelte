<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzwz5-bow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzwz5-bow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:skip-forward" {...props}></Icon>
