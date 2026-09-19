<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9a76dbze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q9a76dbze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:sweden" {...props}></Icon>
