<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5b76tsta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x5b76tsta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-stop-sharp" {...props}></Icon>
