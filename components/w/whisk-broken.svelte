<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dji50-e4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dji50-e4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:whisk-broken" {...props}></Icon>
