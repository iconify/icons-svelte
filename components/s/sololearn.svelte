<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgv0rybkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xgv0rybkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:sololearn" {...props}></Icon>
