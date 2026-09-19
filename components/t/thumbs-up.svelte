<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qaj23_bvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qaj23_bvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:thumbs-up" {...props}></Icon>
