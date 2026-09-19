<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smzo33q6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="smzo33q6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:user-group" {...props}></Icon>
