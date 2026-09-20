<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7q8ynbdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q7q8ynbdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:sailfishos" {...props}></Icon>
