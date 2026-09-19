<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qklygwbjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="qklygwbjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:social-twitter" {...props}></Icon>
