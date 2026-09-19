<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kl-q4qtnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1280,"height":1536};
const content = `<path class="kl-q4qtnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:shield" {...props}></Icon>
