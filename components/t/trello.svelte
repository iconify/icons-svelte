<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgc52eqtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fgc52eqtm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:trello" {...props}></Icon>
