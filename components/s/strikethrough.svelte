<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw8c2qbhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bw8c2qbhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:strikethrough" {...props}></Icon>
