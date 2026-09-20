<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j20ot3geh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j20ot3geh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:toll" {...props}></Icon>
