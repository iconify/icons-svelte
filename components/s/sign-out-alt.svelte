<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx561ngds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sx561ngds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:sign-out-alt" {...props}></Icon>
