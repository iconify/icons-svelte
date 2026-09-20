<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9w8e8rbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l9w8e8rbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:vultr" {...props}></Icon>
