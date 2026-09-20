<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omdqejbnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="omdqejbnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:t-shirt-2-fill" {...props}></Icon>
