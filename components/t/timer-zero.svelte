<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgk3-tb6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zgk3-tb6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:timer-zero" {...props}></Icon>
