<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m91xfrbbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m91xfrbbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:sick" {...props}></Icon>
