<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwjw1vf0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="iwjw1vf0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:test-user-solid" {...props}></Icon>
