<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahdgfnwzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ahdgfnwzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:what3words" {...props}></Icon>
