<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0a4zqmzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q0a4zqmzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:sync-alt" {...props}></Icon>
