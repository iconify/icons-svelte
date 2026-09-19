<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw6s-92eq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":898,"height":1024};
const content = `<path class="qw6s-92eq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:thermometeralt" {...props}></Icon>
