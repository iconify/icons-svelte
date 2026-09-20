<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a57ft7tfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a57ft7tfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:zsh" {...props}></Icon>
