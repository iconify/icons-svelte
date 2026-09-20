<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1lpqyiai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m1lpqyiai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:zlk" {...props}></Icon>
