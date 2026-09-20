<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1m1dcc8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m1m1dcc8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:speedypage" {...props}></Icon>
