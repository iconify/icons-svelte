<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke5xwm82e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ke5xwm82e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:store-look-up-outline" {...props}></Icon>
