<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kg0h9m8rt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kg0h9m8rt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:weight-tilde-solid" {...props}></Icon>
