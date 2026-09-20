<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd6j98biy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nd6j98biy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:user-cross-fill" {...props}></Icon>
