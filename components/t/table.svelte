<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2tj91baw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a2tj91baw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:table" {...props}></Icon>
