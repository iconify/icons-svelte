<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp9a9d94n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xp9a9d94n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:star-duotone" {...props}></Icon>
