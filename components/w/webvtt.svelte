<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngd4hgbau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ngd4hgbau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:webvtt" {...props}></Icon>
