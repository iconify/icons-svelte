<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx3qosbio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="tx3qosbio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:social-lastfm" {...props}></Icon>
