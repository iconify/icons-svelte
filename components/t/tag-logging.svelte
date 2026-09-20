<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2npi2bha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="u2npi2bha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:tag-logging" {...props}></Icon>
