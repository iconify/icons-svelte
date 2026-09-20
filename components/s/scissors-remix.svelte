<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dto5m8b2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dto5m8b2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:scissors-remix" {...props}></Icon>
