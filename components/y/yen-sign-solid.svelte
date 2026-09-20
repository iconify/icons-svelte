<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flkk7eaea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="flkk7eaea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:yen-sign-solid" {...props}></Icon>
