<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmv3c7gqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gmv3c7gqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:t-shirt" {...props}></Icon>
