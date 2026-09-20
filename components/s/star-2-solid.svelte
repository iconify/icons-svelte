<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvpvz45bv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yvpvz45bv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:star-2-solid" {...props}></Icon>
