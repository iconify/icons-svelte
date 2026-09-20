<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5jm7bc9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="f5jm7bc9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:tag" {...props}></Icon>
