<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbryc8qgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pbryc8qgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:scooter-solid" {...props}></Icon>
