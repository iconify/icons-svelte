<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvbq5b4xd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dvbq5b4xd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:times-duotone" {...props}></Icon>
