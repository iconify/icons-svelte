<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmvdr_n-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmvdr_n-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:tooth-alert" {...props}></Icon>
