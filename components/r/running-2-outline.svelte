<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujhv2izwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ujhv2izwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:running-2-outline" {...props}></Icon>
