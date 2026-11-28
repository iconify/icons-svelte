<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebj33kbox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ebj33kbox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:store-solid" {...props}></Icon>
