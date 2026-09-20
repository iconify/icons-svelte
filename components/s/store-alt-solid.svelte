<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie-qqtb5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ie-qqtb5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:store-alt-solid" {...props}></Icon>
