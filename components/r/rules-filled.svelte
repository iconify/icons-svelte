<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6wqijbrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="z6wqijbrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:rules-filled" {...props}></Icon>
