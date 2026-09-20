<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nue2cryyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="nue2cryyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:speaker" {...props}></Icon>
