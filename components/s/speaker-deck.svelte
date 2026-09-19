<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo8q6rzpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eo8q6rzpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:speaker-deck" {...props}></Icon>
