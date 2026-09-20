<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca5y08lpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ca5y08lpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:signature" {...props}></Icon>
