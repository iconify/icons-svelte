<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnpk5mb4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jnpk5mb4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:x-filled" {...props}></Icon>
