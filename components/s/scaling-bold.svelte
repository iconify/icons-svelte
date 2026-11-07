<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxiuf1b8p.css';
import '../../css/j/jq9qq8bcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rxiuf1b8p"/><path class="jq9qq8bcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:scaling-bold" {...props}></Icon>
