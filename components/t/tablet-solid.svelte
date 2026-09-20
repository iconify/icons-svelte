<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-er0dsds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-er0dsds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:tablet-solid" {...props}></Icon>
