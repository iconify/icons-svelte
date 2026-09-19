<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfa2_qe1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kfa2_qe1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:twitch" {...props}></Icon>
