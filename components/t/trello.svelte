<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgulnoykv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bgulnoykv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:trello" {...props}></Icon>
