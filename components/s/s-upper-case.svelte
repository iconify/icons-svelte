<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fu4lnfkov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":431,"height":772};
const content = `<path class="fu4lnfkov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:s-upper-case" {...props}></Icon>
