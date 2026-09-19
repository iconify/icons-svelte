<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dokbrr4ih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dokbrr4ih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:shield-virus" {...props}></Icon>
