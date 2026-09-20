<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fymm-cfdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fymm-cfdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:social-security-administration-dark" {...props}></Icon>
