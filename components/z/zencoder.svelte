<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x33rsnb6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x33rsnb6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:zencoder" {...props}></Icon>
