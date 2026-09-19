<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgy4hvbmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="kgy4hvbmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:sort-numeric-down-alt" {...props}></Icon>
