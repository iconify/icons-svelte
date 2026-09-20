<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcrc-8b3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fcrc-8b3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:sponsor-tiers-24" {...props}></Icon>
