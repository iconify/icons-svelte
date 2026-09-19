<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0m8oyg9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t0m8oyg9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:stop-sharp" {...props}></Icon>
