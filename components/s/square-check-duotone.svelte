<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdrmlmx_y.css';
import '../../css/y/ytv8j6l6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdrmlmx_y"/><path class="ytv8j6l6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:square-check-duotone" {...props}></Icon>
