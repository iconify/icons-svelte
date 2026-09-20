<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwi6y6jmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nwi6y6jmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-half" {...props}></Icon>
