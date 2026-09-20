<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blubov6ot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="blubov6ot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:shelly" {...props}></Icon>
