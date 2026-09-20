<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgpgm4bxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rgpgm4bxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:speaker-deck" {...props}></Icon>
