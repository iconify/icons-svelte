<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzyl80b9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="yzyl80b9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:wordpress-fill" {...props}></Icon>
