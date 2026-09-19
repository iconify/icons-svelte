<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a26dkh2yf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a26dkh2yf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:spotify" {...props}></Icon>
