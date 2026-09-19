<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1ou0nb2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o1ou0nb2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:tram" {...props}></Icon>
