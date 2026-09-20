<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rovboe1ee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rovboe1ee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:travel-bag-2" {...props}></Icon>
