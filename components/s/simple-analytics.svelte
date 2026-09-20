<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzyxvbbxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bzyxvbbxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:simple-analytics" {...props}></Icon>
