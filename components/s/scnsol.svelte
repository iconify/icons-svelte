<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k18jzab8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k18jzab8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:scnsol" {...props}></Icon>
