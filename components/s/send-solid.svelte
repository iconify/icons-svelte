<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inl2l1b8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="inl2l1b8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:send-solid" {...props}></Icon>
