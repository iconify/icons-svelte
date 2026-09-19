<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvoxqobib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dvoxqobib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:user-plus-filled" {...props}></Icon>
