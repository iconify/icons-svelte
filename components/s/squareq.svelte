<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkqn7xbch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="hkqn7xbch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:squareq" {...props}></Icon>
