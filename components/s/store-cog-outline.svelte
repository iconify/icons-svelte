<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5b9i3bmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x5b9i3bmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:store-cog-outline" {...props}></Icon>
