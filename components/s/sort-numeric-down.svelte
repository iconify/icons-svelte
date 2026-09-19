<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjm_ikbdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="kjm_ikbdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:sort-numeric-down" {...props}></Icon>
